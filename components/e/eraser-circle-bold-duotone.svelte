<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrdvcwidb.css';
import '../../css/v/vsmrr13db.css';
import '../../css/c/ch40nbb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrdvcwidb"/><path class="vsmrr13db"/><path class="ch40nbb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eraser-circle-bold-duotone" {...props}></Icon>
