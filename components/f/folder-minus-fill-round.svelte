<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyj9v4bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyj9v4bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-minus-fill-round" {...props}></Icon>
