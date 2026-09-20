<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpqb6fb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gpqb6fb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:inbox-outline" {...props}></Icon>
