<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3mbqmemh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g3mbqmemh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:eternal-vows-dark" {...props}></Icon>
