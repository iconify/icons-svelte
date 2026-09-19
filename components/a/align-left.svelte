<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lddcg3b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lddcg3b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:align-left" {...props}></Icon>
