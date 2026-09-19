<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx7jiwxxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gx7jiwxxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bolas" {...props}></Icon>
