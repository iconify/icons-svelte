<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjva_kt4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjva_kt4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cog-two-solid" {...props}></Icon>
