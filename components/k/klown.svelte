<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/za--gks2g.css';
import '../../css/m/md286fbip.css';
import '../../css/i/i6oojlb1f.css';
import '../../css/p/puadfrbkz.css';
import '../../css/n/n0jgb0b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle class="za--gks2g"/><g class="md286fbip"><path class="i6oojlb1f"/><path class="puadfrbkz"/><path class="n0jgb0b0f"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency-color:klown" {...props}></Icon>
