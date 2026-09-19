<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjq0_3_pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bjq0_3_pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:drum" {...props}></Icon>
