<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfptr2-1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pfptr2-1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-checkmark-empty" {...props}></Icon>
