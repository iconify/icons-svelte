<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oicl4q_ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oicl4q_ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proval-light" {...props}></Icon>
