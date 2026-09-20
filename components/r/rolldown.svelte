<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gn5p7nbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gn5p7nbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rolldown" {...props}></Icon>
