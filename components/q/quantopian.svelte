<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp7js-igc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gp7js-igc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:quantopian" {...props}></Icon>
