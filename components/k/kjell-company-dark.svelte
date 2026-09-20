<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_821ibzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i_821ibzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kjell-company-dark" {...props}></Icon>
