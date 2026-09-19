<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku-6f_b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ku-6f_b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-done" {...props}></Icon>
