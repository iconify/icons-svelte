<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlrgcccrm.css';
import '../../css/o/oqhmv740i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qlrgcccrm"/><path class="oqhmv740i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:prestashop" {...props}></Icon>
