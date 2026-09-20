<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av2burbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av2burbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:creative-commons-sa-fill" {...props}></Icon>
