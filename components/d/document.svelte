<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7rcji-7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q7rcji-7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:document" {...props}></Icon>
