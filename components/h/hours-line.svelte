<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo4uivbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yo4uivbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hours-line" {...props}></Icon>
