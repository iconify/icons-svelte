<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoihlxb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eoihlxb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-right-1-light" {...props}></Icon>
