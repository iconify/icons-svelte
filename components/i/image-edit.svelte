<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r698tjbbz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r698tjbbz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:image-edit" {...props}></Icon>
