<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z51zl_eod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z51zl_eod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-dot-fill" {...props}></Icon>
