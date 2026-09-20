<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwbxz27sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwbxz27sz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:grid2" {...props}></Icon>
