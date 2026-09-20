<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t54_tnbzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t54_tnbzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dental-fill" {...props}></Icon>
