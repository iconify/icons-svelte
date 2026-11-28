<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md75adbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md75adbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:card-diamond" {...props}></Icon>
