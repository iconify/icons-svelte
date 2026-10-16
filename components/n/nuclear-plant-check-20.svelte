<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ily569bri.css';
import '../../css/w/wegqv6blc.css';
import '../../css/z/zsocjwbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ily569bri"/><path class="wegqv6blc"/><path class="zsocjwbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nuclear-plant-check-20" {...props}></Icon>
