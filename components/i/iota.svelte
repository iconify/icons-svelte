<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-ij1pbxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-ij1pbxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:iota" {...props}></Icon>
