<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex2baqp8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ex2baqp8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-euro-fill" {...props}></Icon>
