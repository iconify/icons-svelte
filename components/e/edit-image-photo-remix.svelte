<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkuqenqrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jkuqenqrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:edit-image-photo-remix" {...props}></Icon>
