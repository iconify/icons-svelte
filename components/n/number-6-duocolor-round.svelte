<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sek5qrbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sek5qrbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-6-duocolor-round" {...props}></Icon>
