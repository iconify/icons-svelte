<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f81_s03iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f81_s03iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:back-forth" {...props}></Icon>
