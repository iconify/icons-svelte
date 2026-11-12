<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuscq9bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xuscq9bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:litlyx" {...props}></Icon>
