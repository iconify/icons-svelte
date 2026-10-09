<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3c_73p9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g3c_73p9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:road-20" {...props}></Icon>
