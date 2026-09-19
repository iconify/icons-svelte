<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ji099hjer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ji099hjer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:file" {...props}></Icon>
