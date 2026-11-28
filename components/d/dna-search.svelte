<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln_o54bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln_o54bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dna-search" {...props}></Icon>
