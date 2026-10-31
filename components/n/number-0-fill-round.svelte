<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dai24z1ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dai24z1ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-0-fill-round" {...props}></Icon>
