<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlub4kbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlub4kbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:add-square-line" {...props}></Icon>
