<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sezlb9bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sezlb9bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:question-mark" {...props}></Icon>
