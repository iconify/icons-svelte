<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye3f1bcxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ye3f1bcxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:maximize" {...props}></Icon>
