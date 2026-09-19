<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anwcf1z6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="anwcf1z6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:file-zip" {...props}></Icon>
