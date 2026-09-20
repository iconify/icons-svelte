<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m21o_tg9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m21o_tg9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:preact" {...props}></Icon>
