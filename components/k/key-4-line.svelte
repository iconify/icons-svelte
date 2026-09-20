<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgz7o1bwh.css';
import '../../css/a/atikj6bha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgz7o1bwh"/><circle class="atikj6bha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-4-line" {...props}></Icon>
