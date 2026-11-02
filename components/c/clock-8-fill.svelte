<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-k-0et4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-k-0et4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-8-fill" {...props}></Icon>
