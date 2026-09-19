<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvbnd9bor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvbnd9bor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:browser" {...props}></Icon>
