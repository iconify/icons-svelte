<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djw3wseim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djw3wseim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ansible" {...props}></Icon>
