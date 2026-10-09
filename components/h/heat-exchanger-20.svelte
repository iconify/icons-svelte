<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh4nptbku.css';
import '../../css/t/ttzlj2nix.css';
import '../../css/z/zei7q3mej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rh4nptbku"/><path class="ttzlj2nix"/><path class="zei7q3mej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-exchanger-20" {...props}></Icon>
