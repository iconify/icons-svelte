<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wst584k2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wst584k2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:circle-slash-24" {...props}></Icon>
