<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oum0u3bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oum0u3bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chevrons-left-right" {...props}></Icon>
