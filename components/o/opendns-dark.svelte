<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxsv4ab9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xxsv4ab9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opendns-dark" {...props}></Icon>
