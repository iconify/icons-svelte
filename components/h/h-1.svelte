<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfelj7bsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfelj7bsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:h-1" {...props}></Icon>
