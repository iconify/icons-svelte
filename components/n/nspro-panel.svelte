<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2z8niypl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2z8niypl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nspro-panel" {...props}></Icon>
