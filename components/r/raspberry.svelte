<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kixwr7b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kixwr7b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:raspberry" {...props}></Icon>
