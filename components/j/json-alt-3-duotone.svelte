<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zelwir9wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zelwir9wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:json-alt-3-duotone" {...props}></Icon>
