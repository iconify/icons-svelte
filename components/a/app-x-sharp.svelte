<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gos3aq1fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gos3aq1fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:app-x-sharp" {...props}></Icon>
