<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx5hmupei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nx5hmupei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:crew-united" {...props}></Icon>
