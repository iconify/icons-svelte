<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgv8flbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rgv8flbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:guitar-tele-16" {...props}></Icon>
