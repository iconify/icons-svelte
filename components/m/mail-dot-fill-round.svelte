<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqppe1b0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqppe1b0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mail-dot-fill-round" {...props}></Icon>
