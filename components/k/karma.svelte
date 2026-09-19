<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns5-s36pk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ns5-s36pk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:karma" {...props}></Icon>
