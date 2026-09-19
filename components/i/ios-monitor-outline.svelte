<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5_4c5bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5_4c5bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-monitor-outline" {...props}></Icon>
