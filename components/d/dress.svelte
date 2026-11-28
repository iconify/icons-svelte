<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie0os72rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie0os72rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:dress" {...props}></Icon>
