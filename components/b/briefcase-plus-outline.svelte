<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efo8qcbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efo8qcbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-plus-outline" {...props}></Icon>
