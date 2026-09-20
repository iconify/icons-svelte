<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmnrj9_6h.css';
import '../../css/l/lrkaywonk.css';
import '../../css/a/auxtjjb7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kmnrj9_6h"/><path class="lrkaywonk"/><path class="auxtjjb7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-webpack-open" {...props}></Icon>
