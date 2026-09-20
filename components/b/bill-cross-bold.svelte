<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnx3lyb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xnx3lyb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bill-cross-bold" {...props}></Icon>
