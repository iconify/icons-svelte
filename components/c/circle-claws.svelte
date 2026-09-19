<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs_5vtbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs_5vtbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:circle-claws" {...props}></Icon>
