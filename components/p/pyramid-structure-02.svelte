<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf8489bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf8489bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pyramid-structure-02" {...props}></Icon>
