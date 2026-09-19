<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjoq5hbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjoq5hbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:capybara" {...props}></Icon>
