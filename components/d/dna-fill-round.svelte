<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5e-c1wyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5e-c1wyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:dna-fill-round" {...props}></Icon>
