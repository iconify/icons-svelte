<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg31zhsfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":506,"height":512};
const content = `<path class="hg31zhsfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:dna" {...props}></Icon>
