<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq40t8vnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq40t8vnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:percentage-diamond-solid" {...props}></Icon>
