<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqhk5lcyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqhk5lcyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:no-drug-or-substance" {...props}></Icon>
