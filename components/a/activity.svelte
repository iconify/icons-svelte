<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyi1r0c8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyi1r0c8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:activity" {...props}></Icon>
