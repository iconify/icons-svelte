<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_2exlbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_2exlbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:fish-smoking" {...props}></Icon>
