<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxlptcclx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xxlptcclx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:cup-with-straw-filled" {...props}></Icon>
