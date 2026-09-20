<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qucg9_brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qucg9_brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-neutral-filled" {...props}></Icon>
