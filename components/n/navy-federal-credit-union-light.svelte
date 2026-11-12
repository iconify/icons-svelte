<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m6s0tlgms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m6s0tlgms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:navy-federal-credit-union-light" {...props}></Icon>
