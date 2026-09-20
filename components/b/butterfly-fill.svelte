<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-qv2fnuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-qv2fnuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:butterfly-fill" {...props}></Icon>
