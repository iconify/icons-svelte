<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egjj-sb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="egjj-sb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:arrow-down" {...props}></Icon>
