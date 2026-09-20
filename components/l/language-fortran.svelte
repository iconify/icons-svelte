<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahh5kkqgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahh5kkqgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:language-fortran" {...props}></Icon>
