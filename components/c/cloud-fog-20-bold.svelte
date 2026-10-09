<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_p5btbjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v_p5btbjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-fog-20-bold" {...props}></Icon>
