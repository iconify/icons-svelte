<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f01x5xj_a.css';
import '../../css/n/nevs5g1iv.css';
import '../../css/c/c82dc_b6t.css';
import '../../css/n/nq5xr2_5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="f01x5xj_a"/><path class="nevs5g1iv"/><path class="c82dc_b6t"/><path class="nq5xr2_5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:papua-new-guinea" {...props}></Icon>
