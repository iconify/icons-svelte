<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_on2cm1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_on2cm1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:compress-v" {...props}></Icon>
