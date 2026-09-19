<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkl73enuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkl73enuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rooster" {...props}></Icon>
