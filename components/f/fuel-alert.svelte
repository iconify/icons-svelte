<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq0tsxb8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sq0tsxb8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:fuel-alert" {...props}></Icon>
