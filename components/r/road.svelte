<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hor9gzzrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="hor9gzzrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:road" {...props}></Icon>
