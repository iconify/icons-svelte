<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oefdycc4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="oefdycc4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pause-rectangle-fill" {...props}></Icon>
