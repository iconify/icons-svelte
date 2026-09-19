<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afh5eih4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":387,"height":512};
const content = `<path class="afh5eih4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ooc" {...props}></Icon>
