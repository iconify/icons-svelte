<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwp0snb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwp0snb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:meh-solid" {...props}></Icon>
