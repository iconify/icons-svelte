<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/foh-cvbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="foh-cvbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:input-sparkles-solid" {...props}></Icon>
