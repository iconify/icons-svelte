<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1o-fsx4d.css';
import '../../css/p/pf54fdcpd.css';
import '../../css/o/otww_sbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o1o-fsx4d"/><path class="pf54fdcpd"/><path class="otww_sbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-branch-48-bold" {...props}></Icon>
