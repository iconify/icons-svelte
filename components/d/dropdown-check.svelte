<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eng1o0dzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eng1o0dzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:dropdown-check" {...props}></Icon>
