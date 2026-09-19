<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc7tgwran.css';
import '../../css/r/rv7f2sbom.css';
import '../../css/z/zk1j0x1lv.css';
import '../../css/m/m99nb8bny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nc7tgwran"/><path class="rv7f2sbom"/><path class="zk1j0x1lv"/><path class="m99nb8bny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:memorystore" {...props}></Icon>
