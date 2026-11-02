<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1gagi45t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1gagi45t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-dollar-sign-line" {...props}></Icon>
