<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goc14zbnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="goc14zbnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:lungs-line" {...props}></Icon>
