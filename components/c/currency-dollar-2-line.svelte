<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwu5rjrra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwu5rjrra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-dollar-2-line" {...props}></Icon>
