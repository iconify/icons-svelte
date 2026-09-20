<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs7a4bcmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qs7a4bcmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:refresh-circle-filled" {...props}></Icon>
