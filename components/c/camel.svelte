<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoqv9k94x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eoqv9k94x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:camel" {...props}></Icon>
