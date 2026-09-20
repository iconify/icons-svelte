<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4j5qe54f.css';
import '../../css/p/p2sv7_dap.css';
import '../../css/f/fkg8wdbmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4j5qe54f"/><path class="p2sv7_dap"/><path class="fkg8wdbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ionx" {...props}></Icon>
