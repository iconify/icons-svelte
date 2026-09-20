<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm1w6yb0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vm1w6yb0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:list-down2-filled" {...props}></Icon>
