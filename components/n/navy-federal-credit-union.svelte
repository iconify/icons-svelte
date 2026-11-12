<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co8fiztgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="co8fiztgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:navy-federal-credit-union" {...props}></Icon>
