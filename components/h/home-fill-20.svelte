<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chf27ccsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="chf27ccsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:home-fill-20" {...props}></Icon>
