<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvd1gsics.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvd1gsics"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pisa-tower-line" {...props}></Icon>
