<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fli0rkblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fli0rkblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-compare-2-fill" {...props}></Icon>
