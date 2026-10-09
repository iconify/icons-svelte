<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmhs3ccli.css';
import '../../css/c/cy8_11dig.css';
import '../../css/o/o4-ileblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wmhs3ccli"/><path class="cy8_11dig"/><path class="o4-ileblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:houseboat-48" {...props}></Icon>
