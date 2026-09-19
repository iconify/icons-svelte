<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbt7fulfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hbt7fulfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-bolt" {...props}></Icon>
