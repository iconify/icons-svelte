<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvm_01f-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvm_01f-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quote-square-bold" {...props}></Icon>
