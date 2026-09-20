<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfcrs0smz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tfcrs0smz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:plus-minus-filled" {...props}></Icon>
