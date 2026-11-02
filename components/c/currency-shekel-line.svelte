<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qstgfvbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qstgfvbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:currency-shekel-line" {...props}></Icon>
