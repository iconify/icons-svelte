<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsfklq23s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsfklq23s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:grid-view-line" {...props}></Icon>
