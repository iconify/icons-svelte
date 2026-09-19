<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ces_7v8dp.css';
import '../../css/k/khz-3ib7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ces_7v8dp"/><path class="khz-3ib7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-discord" {...props}></Icon>
