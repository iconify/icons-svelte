<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj2248f8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj2248f8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:jar-x" {...props}></Icon>
