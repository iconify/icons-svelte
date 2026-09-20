<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqvw7_bbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqvw7_bbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:octagon-fill" {...props}></Icon>
