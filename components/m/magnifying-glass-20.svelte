<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwv90_00a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nwv90_00a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:magnifying-glass-20" {...props}></Icon>
