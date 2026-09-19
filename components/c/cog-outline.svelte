<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7f-7pw_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7f-7pw_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:cog-outline" {...props}></Icon>
