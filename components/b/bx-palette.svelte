<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4wxqtb9k.css';
import '../../css/i/i41e6pm1x.css';
import '../../css/l/l1tdjlb-d.css';
import '../../css/b/b12gxvr_k.css';
import '../../css/u/uqsohbb5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4wxqtb9k"/><circle class="i41e6pm1x"/><circle class="l1tdjlb-d"/><circle class="b12gxvr_k"/><circle class="uqsohbb5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-palette" {...props}></Icon>
