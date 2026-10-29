<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz9rdlkfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz9rdlkfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bandage-solid" {...props}></Icon>
