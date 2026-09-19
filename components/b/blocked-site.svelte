<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo9mqglso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="oo9mqglso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:blocked-site" {...props}></Icon>
