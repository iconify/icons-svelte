<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/val914blj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="val914blj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:code-solid" {...props}></Icon>
