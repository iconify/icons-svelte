<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu_-1daos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hu_-1daos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:epsilon" {...props}></Icon>
