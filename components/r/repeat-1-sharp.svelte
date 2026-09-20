<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1ahaabrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1ahaabrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:repeat-1-sharp" {...props}></Icon>
