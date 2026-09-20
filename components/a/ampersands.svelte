<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmh5-ebmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmh5-ebmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:ampersands" {...props}></Icon>
