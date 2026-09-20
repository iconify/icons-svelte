<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eut-2bbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eut-2bbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homematic-ip-light" {...props}></Icon>
