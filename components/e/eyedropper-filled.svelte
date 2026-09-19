<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-0l1ebhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-0l1ebhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eyedropper-filled" {...props}></Icon>
