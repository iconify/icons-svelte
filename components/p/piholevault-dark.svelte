<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cspszkbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cspszkbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piholevault-dark" {...props}></Icon>
