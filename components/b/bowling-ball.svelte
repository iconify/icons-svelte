<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqbkv8u2i.css';
import '../../css/l/l1tdjlb-d.css';
import '../../css/b/b12gxvr_k.css';
import '../../css/r/r_6o9d_-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><circle class="l1tdjlb-d"/><circle class="b12gxvr_k"/><circle class="r_6o9d_-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bowling-ball" {...props}></Icon>
