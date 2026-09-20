<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_-6f0blo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i_-6f0blo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-dollar-fill" {...props}></Icon>
