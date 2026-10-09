<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o05ktk5it.css';
import '../../css/p/pya8cs06p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o05ktk5it"/><path class="pya8cs06p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chef-knife-20" {...props}></Icon>
