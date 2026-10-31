<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccijvbbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccijvbbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:number-0-round" {...props}></Icon>
