<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_dabbeqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="y_dabbeqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:revers" {...props}></Icon>
