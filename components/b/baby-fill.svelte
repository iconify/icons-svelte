<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqp7-xwht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zqp7-xwht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baby-fill" {...props}></Icon>
