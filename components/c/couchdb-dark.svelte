<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuq0ab0qq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uuq0ab0qq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:couchdb-dark" {...props}></Icon>
