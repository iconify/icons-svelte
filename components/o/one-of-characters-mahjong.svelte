<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqi0klb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="oqi0klb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:one-of-characters-mahjong" {...props}></Icon>
