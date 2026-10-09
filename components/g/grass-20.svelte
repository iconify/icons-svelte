<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waz_2hbmd.css';
import '../../css/e/eyzw0tyws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="waz_2hbmd"/><path class="eyzw0tyws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grass-20" {...props}></Icon>
