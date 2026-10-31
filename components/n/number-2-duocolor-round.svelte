<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4-f04bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4-f04bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-2-duocolor-round" {...props}></Icon>
