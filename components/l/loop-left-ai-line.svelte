<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adqbg89ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adqbg89ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loop-left-ai-line" {...props}></Icon>
