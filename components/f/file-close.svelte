<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwj7h0bbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xwj7h0bbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:file-close" {...props}></Icon>
