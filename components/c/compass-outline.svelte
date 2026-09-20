<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zscdv2etd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zscdv2etd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:compass-outline" {...props}></Icon>
