<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv5nqnbux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jv5nqnbux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:magic-lamp" {...props}></Icon>
