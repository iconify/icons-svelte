<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxq6zy91w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxq6zy91w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:keyboard-gloss" {...props}></Icon>
