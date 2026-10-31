<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nr5p_h15c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nr5p_h15c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-8-duocolor-round" {...props}></Icon>
