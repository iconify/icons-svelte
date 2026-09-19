<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvpch3zpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hvpch3zpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:bubble-middle-top-fill" {...props}></Icon>
