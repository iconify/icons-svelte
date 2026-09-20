<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niuq_4bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="niuq_4bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:litellm-light" {...props}></Icon>
