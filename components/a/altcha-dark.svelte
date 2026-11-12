<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyu4b0bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xyu4b0bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:altcha-dark" {...props}></Icon>
