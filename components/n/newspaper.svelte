<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9k5qybjm.css';
import '../../css/v/vjhtv-b4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9k5qybjm"/><path class="vjhtv-b4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:newspaper" {...props}></Icon>
