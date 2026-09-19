<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlom9rblp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tlom9rblp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:flag-objective" {...props}></Icon>
