<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bup0vabrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bup0vabrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-2x3" {...props}></Icon>
