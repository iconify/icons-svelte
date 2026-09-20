<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5-6mmbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="m5-6mmbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:bold-solid" {...props}></Icon>
