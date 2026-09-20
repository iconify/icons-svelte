<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdh5bcc2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wdh5bcc2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:link-break-1" {...props}></Icon>
