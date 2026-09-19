<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7yw8yb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k7yw8yb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:assembly-zilog" {...props}></Icon>
