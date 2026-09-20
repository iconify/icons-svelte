<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfv_stdde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hfv_stdde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-minimalistic-outline" {...props}></Icon>
