<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cng445bcg.css';
import '../../css/p/pzkg8kb5w.css';
import '../../css/t/t5jp7s4kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cng445bcg"/><path class="pzkg8kb5w"/><path class="t5jp7s4kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-case-bold" {...props}></Icon>
