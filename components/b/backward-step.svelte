<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1y5f3xqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1y5f3xqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:backward-step" {...props}></Icon>
