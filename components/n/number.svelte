<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6i4h2b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x6i4h2b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:number" {...props}></Icon>
