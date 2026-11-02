<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr4w21ckn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr4w21ckn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pic-fill" {...props}></Icon>
