<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiwvheg7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="hiwvheg7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:arrow" {...props}></Icon>
