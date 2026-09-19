<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3ovebbay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3ovebbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:entry-door" {...props}></Icon>
