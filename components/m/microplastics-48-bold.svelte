<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbb5sxb8o.css';
import '../../css/g/g74pk9c5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mbb5sxb8o"/><path class="g74pk9c5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:microplastics-48-bold" {...props}></Icon>
