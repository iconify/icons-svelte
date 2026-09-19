<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdo6aybas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdo6aybas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:list-numbered" {...props}></Icon>
