<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8m23wzei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8m23wzei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cairn" {...props}></Icon>
