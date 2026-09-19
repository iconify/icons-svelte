<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab4f0vbkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab4f0vbkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:church" {...props}></Icon>
