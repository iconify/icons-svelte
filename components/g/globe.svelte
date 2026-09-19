<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adeqrsbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adeqrsbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:globe" {...props}></Icon>
