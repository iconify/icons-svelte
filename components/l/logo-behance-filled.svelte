<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2x4qxbpu.css';
import '../../css/g/gwq7723uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2x4qxbpu"/><path class="gwq7723uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-behance-filled" {...props}></Icon>
