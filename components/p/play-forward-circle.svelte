<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak5m796zb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ak5m796zb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:play-forward-circle" {...props}></Icon>
