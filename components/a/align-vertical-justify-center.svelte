<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs6nie1vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs6nie1vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-justify-center" {...props}></Icon>
