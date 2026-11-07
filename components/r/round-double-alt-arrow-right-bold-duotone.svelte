<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrdvcwidb.css';
import '../../css/u/uhl-u5b-k.css';
import '../../css/j/jutrygoyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="uhl-u5b-k"/><path class="jutrygoyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-double-alt-arrow-right-bold-duotone" {...props}></Icon>
