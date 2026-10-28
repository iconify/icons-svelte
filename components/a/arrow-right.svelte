<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck017qboc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck017qboc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:arrow-right" {...props}></Icon>
