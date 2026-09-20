<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkr3ijbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkr3ijbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:essential-ai" {...props}></Icon>
