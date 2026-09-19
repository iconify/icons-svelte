<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4s7seblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q4s7seblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:export" {...props}></Icon>
