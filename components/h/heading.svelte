<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh4avsbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh4avsbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="struq:heading" {...props}></Icon>
