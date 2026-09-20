<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxg1hjyts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxg1hjyts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:chinaeasternairlines" {...props}></Icon>
