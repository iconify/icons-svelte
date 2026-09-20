<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx8vj2brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fx8vj2brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ladder" {...props}></Icon>
