<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2dhjbxgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2dhjbxgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-facebook-filled" {...props}></Icon>
