<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzfegx0sc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="tzfegx0sc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cloud-fail" {...props}></Icon>
