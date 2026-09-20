<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8sh_rchi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8sh_rchi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:border-right" {...props}></Icon>
