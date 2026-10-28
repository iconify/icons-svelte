<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eafin5bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eafin5bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:rocket" {...props}></Icon>
