<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl88tvb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zl88tvb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:crop-fill-round" {...props}></Icon>
