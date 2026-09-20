<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi5alzboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bi5alzboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:documenso-light" {...props}></Icon>
