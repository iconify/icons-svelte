<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glfd-obwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glfd-obwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-project-tc-filled" {...props}></Icon>
