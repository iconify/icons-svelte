<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuup5mbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vuup5mbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:loglibrarian" {...props}></Icon>
