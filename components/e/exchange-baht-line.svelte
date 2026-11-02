<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6f7gj65i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r6f7gj65i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exchange-baht-line" {...props}></Icon>
