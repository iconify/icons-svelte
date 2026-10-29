<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljipl3smr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljipl3smr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:heading-solid" {...props}></Icon>
