<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlzsimbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlzsimbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-3-line" {...props}></Icon>
