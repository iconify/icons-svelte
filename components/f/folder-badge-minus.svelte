<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxztayaou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hxztayaou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:folder-badge-minus" {...props}></Icon>
