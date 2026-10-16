<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz1cr6bmp.css';
import '../../css/t/tvqb9tb9q.css';
import '../../css/f/fm68w8yya.css';
import '../../css/f/fonho850d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pz1cr6bmp"/><path class="tvqb9tb9q"/><path class="fm68w8yya"/><path class="fonho850d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:load-cell-48" {...props}></Icon>
