<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zarsxtjjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zarsxtjjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:lens-fill" {...props}></Icon>
