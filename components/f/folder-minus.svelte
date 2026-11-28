<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj6h01w7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj6h01w7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:folder-minus" {...props}></Icon>
