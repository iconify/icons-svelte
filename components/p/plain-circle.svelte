<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zszfq8dqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zszfq8dqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:plain-circle" {...props}></Icon>
