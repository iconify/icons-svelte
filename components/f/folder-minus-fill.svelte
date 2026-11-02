<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go1mctbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="go1mctbfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-minus-fill" {...props}></Icon>
