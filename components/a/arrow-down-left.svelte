<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6cki_b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6cki_b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:arrow-down-left" {...props}></Icon>
