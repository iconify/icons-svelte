<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnk9fl7li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnk9fl7li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mail-badge-line" {...props}></Icon>
