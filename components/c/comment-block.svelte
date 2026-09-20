<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc7udhbye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc7udhbye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-block" {...props}></Icon>
