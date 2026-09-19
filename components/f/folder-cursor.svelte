<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq78els5g.css';
import '../../css/p/pnp4hqbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sq78els5g"/><path class="pnp4hqbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:folder-cursor" {...props}></Icon>
