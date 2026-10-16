<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr0qdm92e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kr0qdm92e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:info-multiple-filled" {...props}></Icon>
