<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsqgsc7zf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dsqgsc7zf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:paper-bag-folded" {...props}></Icon>
