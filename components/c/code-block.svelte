<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teb7xlbof.css';
import '../../css/m/mnjmwzb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teb7xlbof"/><path class="mnjmwzb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:code-block" {...props}></Icon>
