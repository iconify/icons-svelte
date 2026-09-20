<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtee50-8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="vtee50-8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:duplicate-filled" {...props}></Icon>
