<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zy0ozxmjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zy0ozxmjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-right-bold" {...props}></Icon>
