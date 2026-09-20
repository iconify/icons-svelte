<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht5ptfbxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht5ptfbxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:number-2-box-outline" {...props}></Icon>
