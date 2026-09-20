<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5avnr9yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5avnr9yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-o" {...props}></Icon>
