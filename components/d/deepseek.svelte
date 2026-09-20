<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iln3bfxyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iln3bfxyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:deepseek" {...props}></Icon>
