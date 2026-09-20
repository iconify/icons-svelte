<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p03_kqbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p03_kqbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:contract-across-outline" {...props}></Icon>
