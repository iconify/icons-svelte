<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/g/g2owwz.css';
import '../../css/g/gv_amu.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c g2owwz"/><path class="a0m25c gv_amu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:account-small" {...props}></Icon>
