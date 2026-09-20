<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od2f99bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="od2f99bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-center-line" {...props}></Icon>
