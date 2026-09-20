<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwu1r6bvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwu1r6bvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:kaios" {...props}></Icon>
