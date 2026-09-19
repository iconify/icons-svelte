<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wfc90oerk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wfc90oerk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dizzy-filled" {...props}></Icon>
