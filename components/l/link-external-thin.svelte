<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l42-2yu0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l42-2yu0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:link-external-thin" {...props}></Icon>
