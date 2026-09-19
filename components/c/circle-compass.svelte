<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5phapbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":32};
const content = `<path class="x5phapbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:circle-compass" {...props}></Icon>
