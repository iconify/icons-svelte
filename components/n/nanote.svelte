<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcqbabccs.css';
import '../../css/d/dgwj8cbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zcqbabccs"/><path class="dgwj8cbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nanote" {...props}></Icon>
