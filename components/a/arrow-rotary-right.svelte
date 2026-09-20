<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkq91bbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkq91bbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-rotary-right" {...props}></Icon>
