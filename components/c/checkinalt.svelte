<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw-oc8bqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="gw-oc8bqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:checkinalt" {...props}></Icon>
