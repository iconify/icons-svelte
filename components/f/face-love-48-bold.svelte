<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2neunb3u.css';
import '../../css/v/v4-bvp8bo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n2neunb3u"/><path class="v4-bvp8bo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:face-love-48-bold" {...props}></Icon>
