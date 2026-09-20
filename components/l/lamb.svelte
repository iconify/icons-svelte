<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvvj__u4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvvj__u4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lamb" {...props}></Icon>
