<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs7_5i_hz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fs7_5i_hz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:mailbox-check" {...props}></Icon>
