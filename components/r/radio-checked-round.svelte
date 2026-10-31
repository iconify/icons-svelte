<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2_bmgbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2_bmgbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:radio-checked-round" {...props}></Icon>
