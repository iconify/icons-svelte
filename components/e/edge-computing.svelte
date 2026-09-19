<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cim0r-4qu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cim0r-4qu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:edge-computing" {...props}></Icon>
