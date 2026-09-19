<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eth3w7x-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eth3w7x-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-xing" {...props}></Icon>
