<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mouazacmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mouazacmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:h2" {...props}></Icon>
