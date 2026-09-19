<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8bo_1b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8bo_1b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-felsisk" {...props}></Icon>
