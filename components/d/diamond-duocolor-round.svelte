<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d879w_odg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d879w_odg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-duocolor-round" {...props}></Icon>
