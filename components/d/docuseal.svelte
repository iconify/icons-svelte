<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej0w98jpu.css';
import '../../css/m/mi3skhlne.css';
import '../../css/t/tcg1rxmwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":180,"height":180};
const content = `<circle class="ej0w98jpu"/><path class="mi3skhlne"/><circle class="tcg1rxmwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:docuseal" {...props}></Icon>
