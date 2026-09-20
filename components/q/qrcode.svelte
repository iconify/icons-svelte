<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyx5u8btq.css';
import '../../css/d/d-beombpy.css';
import '../../css/y/ygr8_mw8f.css';
import '../../css/m/myuqn2b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kyx5u8btq"/><path class="d-beombpy"/><path class="ygr8_mw8f"/><path class="myuqn2b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:qrcode" {...props}></Icon>
