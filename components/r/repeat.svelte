<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ade-wbb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ade-wbb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:repeat" {...props}></Icon>
