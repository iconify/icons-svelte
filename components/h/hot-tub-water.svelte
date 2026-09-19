<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rax16kjjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rax16kjjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hot-tub-water" {...props}></Icon>
