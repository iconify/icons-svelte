<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmt6w7bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmt6w7bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dna-check" {...props}></Icon>
