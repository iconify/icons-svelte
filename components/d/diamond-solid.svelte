<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkv30x99a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gkv30x99a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:diamond-solid" {...props}></Icon>
