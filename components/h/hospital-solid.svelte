<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbvy1n6bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbvy1n6bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:hospital-solid" {...props}></Icon>
