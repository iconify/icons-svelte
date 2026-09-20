<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7s-d6ryw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7s-d6ryw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pointer-collaboration" {...props}></Icon>
