<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm2otvbdc.css';
import '../../css/i/icw3oacuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rm2otvbdc"/><path class="icw3oacuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:planka" {...props}></Icon>
