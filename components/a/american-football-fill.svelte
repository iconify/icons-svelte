<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cws1kbczm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cws1kbczm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:american-football-fill" {...props}></Icon>
