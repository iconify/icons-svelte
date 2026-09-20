<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlhk7wqxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qlhk7wqxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:humhub" {...props}></Icon>
