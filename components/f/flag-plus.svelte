<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m59tlb5eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m59tlb5eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:flag-plus" {...props}></Icon>
