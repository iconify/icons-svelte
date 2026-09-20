<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx9irdq5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gx9irdq5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:nswitch" {...props}></Icon>
