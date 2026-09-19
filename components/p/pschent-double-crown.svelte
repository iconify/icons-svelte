<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrc470bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nrc470bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pschent-double-crown" {...props}></Icon>
