<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j52f7_bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j52f7_bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copyright-fill" {...props}></Icon>
