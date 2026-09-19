<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvy1d59je.css';
import '../../css/l/lidjc4bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvy1d59je"/><path class="lidjc4bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:clock-dashed-half" {...props}></Icon>
