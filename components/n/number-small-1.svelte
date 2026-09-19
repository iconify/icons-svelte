<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xzk6xmbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xzk6xmbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:number-small-1" {...props}></Icon>
