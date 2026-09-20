<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bus69jdjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bus69jdjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-infor-line" {...props}></Icon>
