<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g__iqeb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g__iqeb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:khoj-light" {...props}></Icon>
