<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnve-dbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnve-dbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:more-1-line" {...props}></Icon>
