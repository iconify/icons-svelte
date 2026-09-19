<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zai_d5b4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zai_d5b4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-down-right-square" {...props}></Icon>
