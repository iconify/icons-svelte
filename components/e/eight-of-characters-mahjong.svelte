<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li0c3jbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="li0c3jbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:eight-of-characters-mahjong" {...props}></Icon>
