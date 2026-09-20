<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdblbht-m.css';
import '../../css/y/yjqp6ojwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qdblbht-m"/><path class="yjqp6ojwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:postal-light" {...props}></Icon>
