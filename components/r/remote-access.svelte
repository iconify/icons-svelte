<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epyglrb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="epyglrb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:remote-access" {...props}></Icon>
