<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnotr46_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnotr46_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:puzzle-edit" {...props}></Icon>
