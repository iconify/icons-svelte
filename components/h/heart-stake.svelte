<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-o_7bc6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b-o_7bc6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heart-stake" {...props}></Icon>
