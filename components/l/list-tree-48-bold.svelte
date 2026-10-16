<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awl_g5bxw.css';
import '../../css/f/fj2f88bnb.css';
import '../../css/s/sqihr-4zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="awl_g5bxw"/><path class="fj2f88bnb"/><path class="sqihr-4zl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:list-tree-48-bold" {...props}></Icon>
