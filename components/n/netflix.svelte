<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-_it7bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-_it7bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:netflix" {...props}></Icon>
