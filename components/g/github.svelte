<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr1nhacmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="kr1nhacmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:github" {...props}></Icon>
