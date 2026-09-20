<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv7tf3b-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qv7tf3b-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:military-police-officer-with-stop-arm" {...props}></Icon>
