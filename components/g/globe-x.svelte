<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtu1fhbkz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vtu1fhbkz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:globe-x" {...props}></Icon>
