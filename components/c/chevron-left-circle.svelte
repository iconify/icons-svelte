<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mncghvblx.css';
import '../../css/m/mpgu6g9gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="mncghvblx"/><path clip-rule="evenodd" class="mpgu6g9gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:chevron-left-circle" {...props}></Icon>
