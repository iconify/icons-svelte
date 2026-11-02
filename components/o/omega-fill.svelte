<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l99u5r9nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l99u5r9nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:omega-fill" {...props}></Icon>
