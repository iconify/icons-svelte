<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_d16i0-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_d16i0-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:pencil" {...props}></Icon>
