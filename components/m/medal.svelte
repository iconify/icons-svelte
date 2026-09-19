<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf_8c0wnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tf_8c0wnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:medal" {...props}></Icon>
