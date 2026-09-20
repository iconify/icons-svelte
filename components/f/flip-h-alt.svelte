<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa73fq75k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa73fq75k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:flip-h-alt" {...props}></Icon>
