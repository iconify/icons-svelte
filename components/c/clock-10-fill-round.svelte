<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w41lk14vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w41lk14vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-10-fill-round" {...props}></Icon>
