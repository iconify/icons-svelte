<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0h4mgbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c0h4mgbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-thermometer" {...props}></Icon>
