<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw_au-gcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zw_au-gcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-nine-small" {...props}></Icon>
