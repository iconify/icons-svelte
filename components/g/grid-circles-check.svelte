<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c66wt6iaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c66wt6iaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-circles-check" {...props}></Icon>
