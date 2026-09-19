<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h133c6uhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="h133c6uhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:asymmetrik" {...props}></Icon>
