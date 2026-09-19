<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-mf2pbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="a-mf2pbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:menu" {...props}></Icon>
