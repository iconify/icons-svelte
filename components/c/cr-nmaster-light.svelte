<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2crndbgo.css';
import '../../css/c/c3jcscciy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y2crndbgo"/><path class="c3jcscciy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cr-nmaster-light" {...props}></Icon>
