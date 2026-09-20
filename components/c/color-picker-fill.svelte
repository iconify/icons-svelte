<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc1e-pe_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zc1e-pe_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:color-picker-fill" {...props}></Icon>
