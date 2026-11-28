<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k383pcbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k383pcbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-face-circle-look-left-solid" {...props}></Icon>
