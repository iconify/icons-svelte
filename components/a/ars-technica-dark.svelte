<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjqz-ibde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kjqz-ibde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ars-technica-dark" {...props}></Icon>
