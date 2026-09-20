<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aevw-3k9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aevw-3k9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:certificate-outline" {...props}></Icon>
