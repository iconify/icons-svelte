<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucz9flbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ucz9flbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bottled-bolt" {...props}></Icon>
