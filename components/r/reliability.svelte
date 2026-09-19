<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h4b12-bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="h4b12-bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:reliability" {...props}></Icon>
