<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqfj0_b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqfj0_b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:hospital-line" {...props}></Icon>
