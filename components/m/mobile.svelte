<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il2q9bcjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="il2q9bcjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mobile" {...props}></Icon>
