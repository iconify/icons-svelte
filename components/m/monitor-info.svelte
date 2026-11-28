<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nih4i_b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nih4i_b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:monitor-info" {...props}></Icon>
