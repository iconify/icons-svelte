<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-84ape3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="w-84ape3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:delivery-truck-small" {...props}></Icon>
