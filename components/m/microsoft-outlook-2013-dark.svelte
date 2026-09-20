<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we8v5acco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="we8v5acco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-outlook-2013-dark" {...props}></Icon>
