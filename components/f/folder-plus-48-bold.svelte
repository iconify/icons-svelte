<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vrw5zccqv.css';
import '../../css/f/fdnc673tk.css';
import '../../css/w/wa61dab_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vrw5zccqv"/><path class="fdnc673tk"/><path class="wa61dab_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-plus-48-bold" {...props}></Icon>
