<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqf62mbvw.css';
import '../../css/r/rmzj1bb8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hqf62mbvw"/><path class="rmzj1bb8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:3d-software" {...props}></Icon>
