<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlv0inh3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hlv0inh3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-ai" {...props}></Icon>
