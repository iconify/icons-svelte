<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-47clalk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-47clalk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:ball" {...props}></Icon>
