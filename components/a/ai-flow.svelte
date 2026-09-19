<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk6t0lwsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jk6t0lwsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ai-flow" {...props}></Icon>
