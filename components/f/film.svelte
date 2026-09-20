<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqraa8bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mqraa8bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:film" {...props}></Icon>
