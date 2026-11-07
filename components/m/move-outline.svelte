<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aay4mrbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aay4mrbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-outline" {...props}></Icon>
