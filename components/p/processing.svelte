<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paf3y539o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="paf3y539o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:processing" {...props}></Icon>
