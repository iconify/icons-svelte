<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7gceg-_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n7gceg-_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:paperclip-2" {...props}></Icon>
