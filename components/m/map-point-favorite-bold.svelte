<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gajvuebmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gajvuebmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-favorite-bold" {...props}></Icon>
