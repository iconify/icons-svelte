<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enc6bgl8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="enc6bgl8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-up" {...props}></Icon>
