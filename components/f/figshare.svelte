<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrjn6xbzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jrjn6xbzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:figshare" {...props}></Icon>
