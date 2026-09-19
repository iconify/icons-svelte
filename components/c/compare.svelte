<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d49z1cc5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d49z1cc5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:compare" {...props}></Icon>
