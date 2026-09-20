<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1d55jbxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k1d55jbxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:remove-delete-sign-bold" {...props}></Icon>
