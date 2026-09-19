<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj62jbb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jj62jbb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:funnel-fill" {...props}></Icon>
