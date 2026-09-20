<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxfrmfydy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxfrmfydy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-bottom-open-line" {...props}></Icon>
