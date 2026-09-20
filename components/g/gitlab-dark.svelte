<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwvmq7j8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qwvmq7j8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitlab-dark" {...props}></Icon>
