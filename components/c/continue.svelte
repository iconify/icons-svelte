<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f1v5f7rwx.css';
import '../../css/b/b62b46bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":300};
const content = `<g class="ft5dv1b6b"><path class="f1v5f7rwx"/><path class="b62b46bsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:continue" {...props}></Icon>
