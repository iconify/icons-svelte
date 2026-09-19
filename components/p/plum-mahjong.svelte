<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6tswxbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="v6tswxbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:plum-mahjong" {...props}></Icon>
