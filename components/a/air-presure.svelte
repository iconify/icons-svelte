<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onovt9qwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onovt9qwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:air-presure" {...props}></Icon>
