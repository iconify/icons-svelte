<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oeys6obdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oeys6obdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-4" {...props}></Icon>
