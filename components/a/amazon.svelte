<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0czblbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":472};
const content = `<path class="h0czblbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:amazon" {...props}></Icon>
