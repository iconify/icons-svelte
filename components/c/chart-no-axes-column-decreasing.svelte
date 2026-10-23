<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft831i35z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft831i35z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chart-no-axes-column-decreasing" {...props}></Icon>
