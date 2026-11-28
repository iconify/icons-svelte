<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7z0f11bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a7z0f11bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:bottle-x" {...props}></Icon>
