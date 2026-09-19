<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmwk8k2ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmwk8k2ve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:like-solid" {...props}></Icon>
