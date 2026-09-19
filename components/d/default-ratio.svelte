<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ge36teifs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ge36teifs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:default-ratio" {...props}></Icon>
