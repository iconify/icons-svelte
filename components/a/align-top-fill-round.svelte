<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rskpovb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rskpovb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-top-fill-round" {...props}></Icon>
