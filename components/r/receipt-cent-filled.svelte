<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqj1_qbxe.css';
import '../../css/q/qcjhzlq8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kqj1_qbxe"/><path clip-rule="evenodd" class="qcjhzlq8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:receipt-cent-filled" {...props}></Icon>
