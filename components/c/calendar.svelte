<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz_yk4vtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz_yk4vtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:calendar" {...props}></Icon>
