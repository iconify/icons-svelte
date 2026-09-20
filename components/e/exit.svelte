<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciwhunbto.css';
import '../../css/s/sdgejvbhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="ciwhunbto"/><path class="sdgejvbhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:exit" {...props}></Icon>
