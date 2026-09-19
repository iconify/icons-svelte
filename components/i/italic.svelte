<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfe71db5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="tfe71db5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:italic" {...props}></Icon>
