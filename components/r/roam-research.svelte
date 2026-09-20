<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2w32zbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2w32zbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:roam-research" {...props}></Icon>
