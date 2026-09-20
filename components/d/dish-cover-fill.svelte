<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7bld3bqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i7bld3bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dish-cover-fill" {...props}></Icon>
