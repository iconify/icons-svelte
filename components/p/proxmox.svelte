<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2o94vbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v2o94vbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:proxmox" {...props}></Icon>
