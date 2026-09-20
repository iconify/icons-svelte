<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpyn0l9lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpyn0l9lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:repeat" {...props}></Icon>
