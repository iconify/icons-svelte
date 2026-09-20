<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfjvmgb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qfjvmgb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:disconnected-circle" {...props}></Icon>
