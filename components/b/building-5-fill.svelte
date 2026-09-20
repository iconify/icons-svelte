<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cesw2mitc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cesw2mitc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-5-fill" {...props}></Icon>
