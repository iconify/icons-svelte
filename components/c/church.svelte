<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glm38kbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="glm38kbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:church" {...props}></Icon>
