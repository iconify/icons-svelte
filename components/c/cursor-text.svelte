<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv7l-t0wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv7l-t0wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cursor-text" {...props}></Icon>
