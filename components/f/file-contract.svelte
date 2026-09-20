<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of6e34b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="of6e34b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-contract" {...props}></Icon>
