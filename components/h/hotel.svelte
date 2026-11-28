<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tih_i84ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tih_i84ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hotel" {...props}></Icon>
