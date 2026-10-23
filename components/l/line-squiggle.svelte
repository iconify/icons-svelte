<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9t2uf62j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9t2uf62j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:line-squiggle" {...props}></Icon>
