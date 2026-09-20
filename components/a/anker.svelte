<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gurdrgddr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":124,"height":36};
const content = `<path class="gurdrgddr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:anker" {...props}></Icon>
