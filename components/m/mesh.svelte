<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8rwi8_jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b b8rwi8_jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:mesh" {...props}></Icon>
