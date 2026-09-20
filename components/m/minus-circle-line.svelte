<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejmctnbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejmctnbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:minus-circle-line" {...props}></Icon>
