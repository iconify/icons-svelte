<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooq9ajsgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ooq9ajsgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mapping-clear" {...props}></Icon>
