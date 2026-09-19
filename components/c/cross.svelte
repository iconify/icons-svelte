<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le4ed9yxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le4ed9yxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:cross" {...props}></Icon>
