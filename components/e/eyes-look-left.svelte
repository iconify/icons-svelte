<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmx2y7bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tmx2y7bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:eyes-look-left" {...props}></Icon>
