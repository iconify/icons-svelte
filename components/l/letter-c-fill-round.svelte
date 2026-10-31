<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th64kwpje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="th64kwpje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-c-fill-round" {...props}></Icon>
