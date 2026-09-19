<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb02adbwv.css';
import '../../css/z/ze1a4qyku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="rb02adbwv"/><path class="ze1a4qyku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:position-man" {...props}></Icon>
