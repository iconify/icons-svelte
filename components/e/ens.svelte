<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa3k2bkey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa3k2bkey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ens" {...props}></Icon>
