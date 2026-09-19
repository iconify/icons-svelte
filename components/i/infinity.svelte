<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s90ot-1ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="s90ot-1ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:infinity" {...props}></Icon>
