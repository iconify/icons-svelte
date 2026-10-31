<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnpk1ibfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnpk1ibfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:checkbox-fill-round" {...props}></Icon>
