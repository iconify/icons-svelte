<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1bi4bcir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1bi4bcir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:choice-fill" {...props}></Icon>
