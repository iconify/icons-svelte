<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfzfotxoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfzfotxoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:delete" {...props}></Icon>
