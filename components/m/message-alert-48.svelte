<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me-xmbmth.css';
import '../../css/y/y9kkxnfah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="me-xmbmth"/><path class="y9kkxnfah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-alert-48" {...props}></Icon>
