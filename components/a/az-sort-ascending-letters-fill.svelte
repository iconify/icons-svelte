<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4x7zra2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4x7zra2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:az-sort-ascending-letters-fill" {...props}></Icon>
