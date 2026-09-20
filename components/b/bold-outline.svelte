<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aub9hz98j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="aub9hz98j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bold-outline" {...props}></Icon>
