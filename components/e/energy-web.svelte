<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmqol_-wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmqol_-wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:energy-web" {...props}></Icon>
