<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh9bj1pjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh9bj1pjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:minus-hexagon-solid" {...props}></Icon>
