<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxtq1wxot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxtq1wxot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:node-fill" {...props}></Icon>
