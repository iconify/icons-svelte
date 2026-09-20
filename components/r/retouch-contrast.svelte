<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1diztbjw.css';
import '../../css/b/bhl7pu3se.css';
import '../../css/x/xt2z68b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a1diztbjw"/><path class="bhl7pu3se"/><path class="xt2z68b3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:retouch-contrast" {...props}></Icon>
