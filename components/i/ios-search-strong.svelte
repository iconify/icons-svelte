<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/istshsb6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="istshsb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-search-strong" {...props}></Icon>
