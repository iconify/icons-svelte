<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow7wuyz2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow7wuyz2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-favorite-outline" {...props}></Icon>
