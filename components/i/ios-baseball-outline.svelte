<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8s1c9zwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e8s1c9zwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-baseball-outline" {...props}></Icon>
