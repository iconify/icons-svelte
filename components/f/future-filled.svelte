<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf-767cdz.css';
import '../../css/l/lidjc4bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf-767cdz"/><path class="lidjc4bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:future-filled" {...props}></Icon>
