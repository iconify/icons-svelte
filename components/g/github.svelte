<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isdc2k3ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1504};
const content = `<path class="isdc2k3ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:github" {...props}></Icon>
