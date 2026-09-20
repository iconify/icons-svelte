<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiy1jzyap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiy1jzyap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home-hashtag-filled" {...props}></Icon>
