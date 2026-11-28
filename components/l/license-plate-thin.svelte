<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibi5hccgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ibi5hccgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:license-plate-thin" {...props}></Icon>
