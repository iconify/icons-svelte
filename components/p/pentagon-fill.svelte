<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex-8-wbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex-8-wbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pentagon-fill" {...props}></Icon>
