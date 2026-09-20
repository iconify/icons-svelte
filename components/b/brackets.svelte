<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqsq_tbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yqsq_tbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:brackets" {...props}></Icon>
