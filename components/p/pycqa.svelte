<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi7cp4t_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi7cp4t_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:pycqa" {...props}></Icon>
