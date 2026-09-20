<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abc94bc3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="abc94bc3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:miro" {...props}></Icon>
