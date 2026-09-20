<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ld8kjwf-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ld8kjwf-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:maximize5" {...props}></Icon>
