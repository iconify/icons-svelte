<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z34xi1b4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z34xi1b4p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-up-circle-fill" {...props}></Icon>
