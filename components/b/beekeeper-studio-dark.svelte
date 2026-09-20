<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umr1o5bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="umr1o5bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beekeeper-studio-dark" {...props}></Icon>
