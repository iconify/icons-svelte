<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic_al5yga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic_al5yga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:octopus" {...props}></Icon>
