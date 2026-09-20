<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvl8subgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pvl8subgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:objective-c" {...props}></Icon>
