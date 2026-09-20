<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so4b4tb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="so4b4tb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:component-none" {...props}></Icon>
