<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ho2uy5bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ho2uy5bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:balance-line" {...props}></Icon>
