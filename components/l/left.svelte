<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4gessbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":7,"height":16};
const content = `<path class="h4gessbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:left" {...props}></Icon>
