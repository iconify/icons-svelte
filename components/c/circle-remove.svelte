<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rot8tbcdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rot8tbcdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:circle-remove" {...props}></Icon>
