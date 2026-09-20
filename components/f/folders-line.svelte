<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy1qk7dzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jy1qk7dzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folders-line" {...props}></Icon>
