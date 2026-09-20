<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z13_dp0su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="z13_dp0su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:on-off-16" {...props}></Icon>
