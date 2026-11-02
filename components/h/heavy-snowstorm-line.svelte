<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-frwh58z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-frwh58z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-snowstorm-line" {...props}></Icon>
