<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut5oznbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut5oznbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:chevron-down" {...props}></Icon>
