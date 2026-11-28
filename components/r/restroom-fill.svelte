<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afo1ixbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="afo1ixbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:restroom-fill" {...props}></Icon>
