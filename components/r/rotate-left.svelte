<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye9asyf6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ye9asyf6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:rotate-left" {...props}></Icon>
