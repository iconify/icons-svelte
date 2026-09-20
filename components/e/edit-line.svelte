<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utjuaibbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="utjuaibbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-line" {...props}></Icon>
