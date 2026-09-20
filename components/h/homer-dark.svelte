<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txfrc-r3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="txfrc-r3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homer-dark" {...props}></Icon>
