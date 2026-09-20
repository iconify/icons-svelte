<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbte5umki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbte5umki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:phone" {...props}></Icon>
