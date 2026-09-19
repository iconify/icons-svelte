<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arezy-bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="arezy-bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:archive" {...props}></Icon>
