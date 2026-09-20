<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlhv9ehzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlhv9ehzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dividing-line-line" {...props}></Icon>
