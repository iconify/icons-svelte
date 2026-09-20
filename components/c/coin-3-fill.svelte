<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk585tbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk585tbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:coin-3-fill" {...props}></Icon>
