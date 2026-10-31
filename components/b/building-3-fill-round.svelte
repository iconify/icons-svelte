<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcnuuetab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcnuuetab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-3-fill-round" {...props}></Icon>
