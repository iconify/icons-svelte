<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_x1y4muz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_x1y4muz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:hashnode" {...props}></Icon>
