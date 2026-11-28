<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjbym0xls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rjbym0xls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heading-1-duotone" {...props}></Icon>
