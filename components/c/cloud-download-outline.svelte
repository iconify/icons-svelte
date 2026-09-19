<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elcyybcku.css';
import '../../css/e/e132nkbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elcyybcku"/><path class="e132nkbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:cloud-download-outline" {...props}></Icon>
