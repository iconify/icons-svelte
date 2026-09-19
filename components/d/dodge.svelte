<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9vvpq57a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g9vvpq57a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:dodge" {...props}></Icon>
