<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3d0l7jvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n3d0l7jvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:flag-fill-20" {...props}></Icon>
