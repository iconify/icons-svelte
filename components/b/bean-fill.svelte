<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qse_z8bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qse_z8bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bean-fill" {...props}></Icon>
