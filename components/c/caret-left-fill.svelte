<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu9b4b9-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu9b4b9-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:caret-left-fill" {...props}></Icon>
