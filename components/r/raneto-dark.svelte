<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc19hobba.css';
import '../../css/g/gd6c7lbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kc19hobba"/><path class="gd6c7lbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raneto-dark" {...props}></Icon>
