<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipt536azn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ipt536azn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:dice-6-solid" {...props}></Icon>
