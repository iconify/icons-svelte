<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp7a2ob2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zp7a2ob2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:creativity-idea-strategy" {...props}></Icon>
