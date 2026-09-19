<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6ze7jbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="d6ze7jbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mortar-pestle" {...props}></Icon>
