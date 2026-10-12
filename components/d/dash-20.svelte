<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6vxljv5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o6vxljv5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:dash-20" {...props}></Icon>
