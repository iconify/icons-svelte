<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oie_c_l0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oie_c_l0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:pencil-square" {...props}></Icon>
