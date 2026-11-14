<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aux3m8cjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aux3m8cjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:activity" {...props}></Icon>
