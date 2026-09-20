<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9kbj8-pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9kbj8-pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:imou" {...props}></Icon>
