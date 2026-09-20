<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on0f48l7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on0f48l7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:frame4-filled" {...props}></Icon>
