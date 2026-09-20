<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8-k94bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b8-k94bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:object-group-solid" {...props}></Icon>
