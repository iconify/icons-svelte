<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz1l0whfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz1l0whfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bed-double" {...props}></Icon>
