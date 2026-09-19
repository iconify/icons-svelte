<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1jdi4cpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="d1jdi4cpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:earth-atlantic" {...props}></Icon>
