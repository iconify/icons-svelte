<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjz9qtsne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjz9qtsne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:link" {...props}></Icon>
