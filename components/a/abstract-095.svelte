<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoyw6ibyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qoyw6ibyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-095" {...props}></Icon>
