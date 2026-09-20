<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf4j0wbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zf4j0wbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:jump" {...props}></Icon>
