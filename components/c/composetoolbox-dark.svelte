<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzwc3f7as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nzwc3f7as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:composetoolbox-dark" {...props}></Icon>
