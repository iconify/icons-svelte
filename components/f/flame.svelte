<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq-hj9bnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq-hj9bnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:flame" {...props}></Icon>
