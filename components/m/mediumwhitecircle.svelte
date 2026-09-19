<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3p8w_7pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="m3p8w_7pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:mediumwhitecircle" {...props}></Icon>
