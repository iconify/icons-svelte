<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj55x0s_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj55x0s_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pixabay" {...props}></Icon>
