<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkjwy9uqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nkjwy9uqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:brave-dark" {...props}></Icon>
