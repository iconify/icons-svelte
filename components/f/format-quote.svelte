<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-fm_yoxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="o-fm_yoxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-quote" {...props}></Icon>
