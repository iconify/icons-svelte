<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnn050b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnn050b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pillar-turaco-short" {...props}></Icon>
