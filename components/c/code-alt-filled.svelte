<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wea5057ad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wea5057ad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:code-alt-filled" {...props}></Icon>
