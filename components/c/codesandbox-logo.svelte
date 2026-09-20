<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mx981cbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mx981cbri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:codesandbox-logo" {...props}></Icon>
