<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk2by8bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk2by8bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-sliders-line" {...props}></Icon>
