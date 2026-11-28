<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apa-j2nit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apa-j2nit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:acorn" {...props}></Icon>
