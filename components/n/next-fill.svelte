<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wa8hrrbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wa8hrrbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:next-fill" {...props}></Icon>
