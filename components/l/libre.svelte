<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3tprn_1p.css';
import '../../css/e/e35tycczk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3tprn_1p"/><path class="e35tycczk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:libre" {...props}></Icon>
