<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7e3msbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="c7e3msbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:folder-blank" {...props}></Icon>
