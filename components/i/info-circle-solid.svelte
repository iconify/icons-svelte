<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l25a_acmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l25a_acmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:info-circle-solid" {...props}></Icon>
