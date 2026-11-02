<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu-9zjbvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu-9zjbvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:happy-fill" {...props}></Icon>
