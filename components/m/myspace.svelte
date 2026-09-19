<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq-o1-bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="oq-o1-bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:myspace" {...props}></Icon>
