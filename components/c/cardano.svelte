<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hir999tlf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hir999tlf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cardano" {...props}></Icon>
