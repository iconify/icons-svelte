<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6op_fa0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6op_fa0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:printer" {...props}></Icon>
