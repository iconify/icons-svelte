<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4tf1rnas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i4tf1rnas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:nailed-foot" {...props}></Icon>
