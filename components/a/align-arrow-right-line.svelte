<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8781o6pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8781o6pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-arrow-right-line" {...props}></Icon>
