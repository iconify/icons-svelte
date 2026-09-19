<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymmm_yblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ymmm_yblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-snow" {...props}></Icon>
