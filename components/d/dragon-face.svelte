<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m66b2hgdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m66b2hgdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:dragon-face" {...props}></Icon>
