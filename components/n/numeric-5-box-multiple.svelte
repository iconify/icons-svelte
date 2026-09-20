<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epst0e1jr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epst0e1jr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:numeric-5-box-multiple" {...props}></Icon>
