<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jozze0brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jozze0brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-audio" {...props}></Icon>
