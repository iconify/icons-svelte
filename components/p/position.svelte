<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stgrhqeqj.css';
import '../../css/r/rb02adbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="stgrhqeqj"/><path class="rb02adbwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:position" {...props}></Icon>
