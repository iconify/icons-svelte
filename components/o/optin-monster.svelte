<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqc-qrqqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="gqc-qrqqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:optin-monster" {...props}></Icon>
