<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0m6_7bfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b0m6_7bfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-vertical-distribute-start-filled" {...props}></Icon>
