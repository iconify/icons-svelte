<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/silr-gb_u.css';
import '../../css/t/tdqcdzb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="silr-gb_u"/><path class="tdqcdzb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:envelope-open-20-bold" {...props}></Icon>
