<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhd2w0b6x.css';
import '../../css/a/a8e-e4bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhd2w0b6x"/><path clip-rule="evenodd" class="a8e-e4bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:confirmations-3-filled" {...props}></Icon>
