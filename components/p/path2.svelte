<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjldq36og.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjldq36og"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:path2" {...props}></Icon>
