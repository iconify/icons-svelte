<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5my-u8du.css';
import '../../css/a/atca9c2ie.css';
import '../../css/t/tp4af3bvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h5my-u8du"/><path class="atca9c2ie"/><path class="tp4af3bvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proton-lumo-light" {...props}></Icon>
