<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/minh_dbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="minh_dbxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database-gear" {...props}></Icon>
