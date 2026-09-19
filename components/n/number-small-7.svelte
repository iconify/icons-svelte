<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxq749buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vxq749buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-small-7" {...props}></Icon>
