<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djsqtnb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="djsqtnb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:modulz-logo" {...props}></Icon>
