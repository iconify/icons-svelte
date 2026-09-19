<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4__6lb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="n4__6lb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:extent-alt" {...props}></Icon>
