<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr6e9l_5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr6e9l_5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:chevron-right" {...props}></Icon>
