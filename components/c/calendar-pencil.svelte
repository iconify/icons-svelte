<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-ndi-n9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="b-ndi-n9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-pencil" {...props}></Icon>
