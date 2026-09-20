<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdvn_thzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qdvn_thzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ovh-dark" {...props}></Icon>
