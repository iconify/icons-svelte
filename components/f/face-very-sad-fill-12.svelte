<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l39qosc6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l39qosc6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:face-very-sad-fill-12" {...props}></Icon>
