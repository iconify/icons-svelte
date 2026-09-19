<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp22x-rfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xp22x-rfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:color-fill-outline" {...props}></Icon>
