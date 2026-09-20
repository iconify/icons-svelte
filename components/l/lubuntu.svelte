<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9y1vebjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9y1vebjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lubuntu" {...props}></Icon>
