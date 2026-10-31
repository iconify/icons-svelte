<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6kzt5bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6kzt5bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:rotate-left-round" {...props}></Icon>
