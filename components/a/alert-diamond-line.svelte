<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zbj_d9baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zbj_d9baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alert-diamond-line" {...props}></Icon>
