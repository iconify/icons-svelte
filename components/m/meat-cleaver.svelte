<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auewfhv9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="auewfhv9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:meat-cleaver" {...props}></Icon>
