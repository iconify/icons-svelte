<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id42arbvz.css';
import '../../css/u/uaycyrbmu.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="id42arbvz"/><path class="clr-i-alert uaycyrbmu"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:map-solid-alerted" {...props}></Icon>
