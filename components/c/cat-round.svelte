<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm3fm8bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm3fm8bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cat-round" {...props}></Icon>
