<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs1be3nix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zs1be3nix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:h3" {...props}></Icon>
