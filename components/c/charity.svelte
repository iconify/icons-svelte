<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g69w9nb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g69w9nb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:charity" {...props}></Icon>
