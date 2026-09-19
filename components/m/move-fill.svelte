<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6sb9-bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j6sb9-bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:move-fill" {...props}></Icon>
