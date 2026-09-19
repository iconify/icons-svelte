<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ml-e1vb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ml-e1vb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-volume-up" {...props}></Icon>
