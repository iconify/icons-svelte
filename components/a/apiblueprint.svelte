<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mixj4hbyv.css';
import '../../css/e/e78ovcj5m.css';
import '../../css/a/avf63ltwu.css';
import '../../css/b/b3w4k5oip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<rect class="mixj4hbyv"/><rect class="e78ovcj5m"/><rect class="avf63ltwu"/><path class="b3w4k5oip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:apiblueprint" {...props}></Icon>
