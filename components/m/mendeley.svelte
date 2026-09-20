<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfac0l_-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfac0l_-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:mendeley" {...props}></Icon>
