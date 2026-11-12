<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xatinu_2d.css';
import '../../css/v/v1w24bcca.css';
import '../../css/c/cn8nznbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xatinu_2d"/><path class="v1w24bcca"/><path class="cn8nznbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:comentario" {...props}></Icon>
