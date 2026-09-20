<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgmjinb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hgmjinb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:divider-vertical" {...props}></Icon>
