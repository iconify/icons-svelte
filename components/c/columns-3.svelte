<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nie1e_bfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nie1e_bfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:columns-3" {...props}></Icon>
