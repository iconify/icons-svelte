<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_gz41biv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_gz41biv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:apm-terminals" {...props}></Icon>
