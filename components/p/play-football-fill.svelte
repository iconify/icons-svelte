<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvq5z1btt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvq5z1btt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:play-football-fill" {...props}></Icon>
