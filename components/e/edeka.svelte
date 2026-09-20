<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm_ewpblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vm_ewpblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:edeka" {...props}></Icon>
