<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rin3p3brc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rin3p3brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:briefcase" {...props}></Icon>
