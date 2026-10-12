<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qahyg6byo.css';
import '../../css/u/uyt0x-bnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qahyg6byo"/><path clip-rule="evenodd" class="uyt0x-bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-stop-filled" {...props}></Icon>
