<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh4z5kbri.css';
import '../../css/y/y2a9lnbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="vh4z5kbri"/><circle class="y2a9lnbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:livinity" {...props}></Icon>
