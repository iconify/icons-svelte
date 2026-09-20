<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtu2yutov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtu2yutov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:99designs" {...props}></Icon>
