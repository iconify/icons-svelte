<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa28y5a1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="qa28y5a1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:brailler" {...props}></Icon>
