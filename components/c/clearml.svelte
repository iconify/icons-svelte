<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrintoagj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrintoagj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:clearml" {...props}></Icon>
