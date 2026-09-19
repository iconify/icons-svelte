<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b261mqb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b261mqb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:alien-egg" {...props}></Icon>
