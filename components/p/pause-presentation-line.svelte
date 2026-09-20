<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvow-absf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvow-absf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pause-presentation-line" {...props}></Icon>
