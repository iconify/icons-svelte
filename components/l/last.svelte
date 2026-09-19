<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1qxa2w7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="z1qxa2w7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:last" {...props}></Icon>
