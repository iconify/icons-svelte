<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilgdwwafm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ilgdwwafm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-round-up" {...props}></Icon>
