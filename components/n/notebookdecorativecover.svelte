<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao_coaa1a.css';
import '../../css/o/o6g1-kwkw.css';
import '../../css/s/so1r549_h.css';
import '../../css/t/t4d2qxx5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ao_coaa1a"/><path class="o6g1-kwkw"/><path class="so1r549_h"/><path class="t4d2qxx5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:notebookdecorativecover" {...props}></Icon>
