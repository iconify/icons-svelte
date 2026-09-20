<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk5j5hbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xk5j5hbpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calculator-sharp-fill" {...props}></Icon>
