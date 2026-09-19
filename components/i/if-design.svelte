<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5e_gbbhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5e_gbbhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:if-design" {...props}></Icon>
