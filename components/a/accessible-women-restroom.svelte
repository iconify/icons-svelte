<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsyqg_0ex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jsyqg_0ex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:accessible-women-restroom" {...props}></Icon>
