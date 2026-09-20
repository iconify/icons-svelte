<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hccjpqwdn.css';
import '../../css/s/sgpjj4b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hccjpqwdn"/><path class="sgpjj4b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dynamodb-dashboard-dark" {...props}></Icon>
