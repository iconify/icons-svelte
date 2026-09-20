<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snvwku1se.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snvwku1se"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:hospital-square-sign" {...props}></Icon>
