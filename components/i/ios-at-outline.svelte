<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wee0a9bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wee0a9bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-at-outline" {...props}></Icon>
