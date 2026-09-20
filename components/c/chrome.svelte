<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwzk-nyrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gwzk-nyrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:chrome" {...props}></Icon>
