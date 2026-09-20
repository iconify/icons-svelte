<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_utkbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ca_utkbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-dancing-with-person-wearing-dress" {...props}></Icon>
