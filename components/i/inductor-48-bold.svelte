<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4jd6hbxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i4jd6hbxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:inductor-48-bold" {...props}></Icon>
