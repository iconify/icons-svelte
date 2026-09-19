<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qilianfni.css';
import '../../css/c/c2wbpkxmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qilianfni"/><path class="c2wbpkxmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:face-alt-filled" {...props}></Icon>
