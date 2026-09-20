<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vctvmtjcb.css';
import '../../css/a/a6eo7ib1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vctvmtjcb"/><path class="a6eo7ib1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dynamodb-dashboard" {...props}></Icon>
