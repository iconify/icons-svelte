<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ouera-xzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ouera-xzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:microsoftonedrive" {...props}></Icon>
