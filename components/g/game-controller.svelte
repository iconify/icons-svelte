<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9mfutbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g9mfutbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:game-controller" {...props}></Icon>
