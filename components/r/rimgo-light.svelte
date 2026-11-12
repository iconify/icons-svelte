<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q615-bq5v.css';
import '../../css/k/k-og-_b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q615-bq5v"/><circle class="k-og-_b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rimgo-light" {...props}></Icon>
