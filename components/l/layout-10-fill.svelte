<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mniiu69wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mniiu69wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-10-fill" {...props}></Icon>
