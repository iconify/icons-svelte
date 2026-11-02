<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8nls8u2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8nls8u2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:midi-fill" {...props}></Icon>
