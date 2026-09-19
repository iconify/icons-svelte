<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa2vsbctw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":464};
const content = `<path class="oa2vsbctw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:input-antenna" {...props}></Icon>
