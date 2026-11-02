<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg-n1kdas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fg-n1kdas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-minus-fill" {...props}></Icon>
