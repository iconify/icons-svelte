<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6rceob1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y6rceob1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:eight-of-bamboos-mahjong" {...props}></Icon>
