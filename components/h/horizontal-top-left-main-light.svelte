<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecbe8r41d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecbe8r41d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:horizontal-top-left-main-light" {...props}></Icon>
