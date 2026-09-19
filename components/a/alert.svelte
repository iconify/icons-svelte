<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4tx97b7q.css';
import '../../css/x/x-ff3h11f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s4tx97b7q"/><circle class="x-ff3h11f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:alert" {...props}></Icon>
