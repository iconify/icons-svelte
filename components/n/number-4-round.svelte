<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8l_brb1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8l_brb1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-4-round" {...props}></Icon>
