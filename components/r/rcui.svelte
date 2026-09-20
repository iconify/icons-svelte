<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbfficpwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1280,"height":1280};
const content = `<path class="gbfficpwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rcui" {...props}></Icon>
