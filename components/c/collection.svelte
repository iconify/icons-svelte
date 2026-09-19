<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4hz1de1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f4hz1de1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:collection" {...props}></Icon>
