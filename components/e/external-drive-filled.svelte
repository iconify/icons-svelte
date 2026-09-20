<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvlmg9bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvlmg9bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:external-drive-filled" {...props}></Icon>
