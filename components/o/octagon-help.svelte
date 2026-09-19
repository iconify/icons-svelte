<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szo_c1lgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szo_c1lgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:octagon-help" {...props}></Icon>
