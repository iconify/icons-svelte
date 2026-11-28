<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzsf0vb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzsf0vb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chalkboard" {...props}></Icon>
