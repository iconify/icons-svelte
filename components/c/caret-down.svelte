<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnb6en77t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnb6en77t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:caret-down" {...props}></Icon>
