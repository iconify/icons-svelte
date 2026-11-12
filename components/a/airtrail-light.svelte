<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2kge_box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b2kge_box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:airtrail-light" {...props}></Icon>
