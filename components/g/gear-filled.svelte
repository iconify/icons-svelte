<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofbirtxga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ofbirtxga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:gear-filled" {...props}></Icon>
