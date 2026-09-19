<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u00i3huun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u00i3huun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:moon" {...props}></Icon>
