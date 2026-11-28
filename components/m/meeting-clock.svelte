<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kj7yb0bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kj7yb0bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:meeting-clock" {...props}></Icon>
