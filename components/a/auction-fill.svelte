<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz-u9wvbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz-u9wvbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:auction-fill" {...props}></Icon>
