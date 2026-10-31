<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv2gc5bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv2gc5bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:database-minus-corner-round" {...props}></Icon>
