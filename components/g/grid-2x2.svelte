<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqchg_bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqchg_bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:grid-2x2" {...props}></Icon>
