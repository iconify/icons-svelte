<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cugntf3hv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cugntf3hv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:mic" {...props}></Icon>
