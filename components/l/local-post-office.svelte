<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9ar7ibgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="h9ar7ibgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-post-office" {...props}></Icon>
