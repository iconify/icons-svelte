<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s50rjobvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="s50rjobvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:envato" {...props}></Icon>
