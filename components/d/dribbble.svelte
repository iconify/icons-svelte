<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7t4ufb7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7t4ufb7m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:dribbble" {...props}></Icon>
