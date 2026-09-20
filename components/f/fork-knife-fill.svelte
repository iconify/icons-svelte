<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e3vwhccem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3vwhccem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fork-knife-fill" {...props}></Icon>
