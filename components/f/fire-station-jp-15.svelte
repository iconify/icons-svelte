<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smckz5bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="smckz5bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:fire-station-jp-15" {...props}></Icon>
