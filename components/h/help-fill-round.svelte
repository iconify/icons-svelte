<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv751gbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wv751gbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:help-fill-round" {...props}></Icon>
