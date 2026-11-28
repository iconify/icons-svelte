<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs1_ig4jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hs1_ig4jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-delay" {...props}></Icon>
