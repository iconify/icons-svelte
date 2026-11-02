<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiiu3qbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiiu3qbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flag-2-fill" {...props}></Icon>
