<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo63jq8fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fo63jq8fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:key-check" {...props}></Icon>
