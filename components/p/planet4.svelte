<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxfh6lbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zxfh6lbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:planet4" {...props}></Icon>
