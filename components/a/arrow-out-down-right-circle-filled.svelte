<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-gja2bhg.css';
import '../../css/k/kpu7t4bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-gja2bhg"/><path class="kpu7t4bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-right-circle-filled" {...props}></Icon>
