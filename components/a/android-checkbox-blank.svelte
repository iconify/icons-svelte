<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmccvoyjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qmccvoyjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-checkbox-blank" {...props}></Icon>
