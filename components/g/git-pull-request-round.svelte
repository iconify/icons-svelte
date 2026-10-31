<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yszcwkbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yszcwkbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-pull-request-round" {...props}></Icon>
