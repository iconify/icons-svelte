<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iudf_ab8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iudf_ab8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:border-outside" {...props}></Icon>
