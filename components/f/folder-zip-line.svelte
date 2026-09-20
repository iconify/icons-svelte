<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jckk0c03o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jckk0c03o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-zip-line" {...props}></Icon>
