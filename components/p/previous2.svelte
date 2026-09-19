<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh07j0b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hh07j0b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:previous2" {...props}></Icon>
