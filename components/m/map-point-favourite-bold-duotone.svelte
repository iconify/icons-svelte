<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z21mj8tjd.css';
import '../../css/c/c5u_5lf0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z21mj8tjd"/><path class="c5u_5lf0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-favourite-bold-duotone" {...props}></Icon>
